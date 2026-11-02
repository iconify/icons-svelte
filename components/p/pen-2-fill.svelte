<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac-5x1biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac-5x1biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-2-fill" {...props}></Icon>
