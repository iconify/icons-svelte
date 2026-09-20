<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a622r-z7c.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="a622r-z7c"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:brown-flag" {...props}></Icon>
