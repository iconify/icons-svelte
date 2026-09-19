<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob6fqnbja.css';
import '../../css/u/u0bpkj-iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ob6fqnbja"/><path class="u0bpkj-iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bookmarks-outline" {...props}></Icon>
