<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icg6lubjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icg6lubjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-2-fill" {...props}></Icon>
