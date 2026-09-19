<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk90xgbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pk90xgbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-rewind" {...props}></Icon>
