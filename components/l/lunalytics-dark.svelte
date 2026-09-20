<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfoa1mbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfoa1mbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lunalytics-dark" {...props}></Icon>
