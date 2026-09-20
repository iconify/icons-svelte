<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm6m-bc7r.css';
import '../../css/k/kwze97erm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lm6m-bc7r"/><path class="kwze97erm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:diamond-suit" {...props}></Icon>
