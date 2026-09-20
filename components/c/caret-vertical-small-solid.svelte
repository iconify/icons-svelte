<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysswcofiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ysswcofiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:caret-vertical-small-solid" {...props}></Icon>
