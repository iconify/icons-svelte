<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp2pmeb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="pp2pmeb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:reply" {...props}></Icon>
