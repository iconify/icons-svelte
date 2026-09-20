<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3rsgcczs.css';
import '../../css/g/ghc79-30g.css';
import '../../css/l/lxc3j5b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="e3rsgcczs"/><path class="ghc79-30g"/><path class="lxc3j5b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kiro" {...props}></Icon>
