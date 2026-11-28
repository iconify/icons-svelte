<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b25cx9bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b25cx9bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:badge-percent-check" {...props}></Icon>
