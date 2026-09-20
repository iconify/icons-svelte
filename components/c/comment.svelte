<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1_vj5bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f1_vj5bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment" {...props}></Icon>
