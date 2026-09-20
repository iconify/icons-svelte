<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x870m4u-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x870m4u-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:couch" {...props}></Icon>
