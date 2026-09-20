<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqcm5_b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqcm5_b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:redo-24" {...props}></Icon>
