<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9q8d4e-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9q8d4e-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-up-fill" {...props}></Icon>
