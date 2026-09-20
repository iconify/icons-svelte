<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh_sqt51j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kh_sqt51j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:caret-vertical-small-outline" {...props}></Icon>
