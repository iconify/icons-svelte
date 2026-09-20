<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3df4fblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3df4fblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drive-fill" {...props}></Icon>
