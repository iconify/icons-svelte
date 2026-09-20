<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnqa97brp.css';
import '../../css/b/bm4a6ibol.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cnqa97brp"/><path class="bm4a6ibol"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-somalia" {...props}></Icon>
