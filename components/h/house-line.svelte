<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk3e8abzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk3e8abzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-line" {...props}></Icon>
