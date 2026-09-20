<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq-fxh_-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jq-fxh_-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:play-structure-with-slide" {...props}></Icon>
