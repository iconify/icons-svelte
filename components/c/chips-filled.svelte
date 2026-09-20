<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac-lxcc5p.css';
import '../../css/o/ofxdamrpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ac-lxcc5p"/><path class="ofxdamrpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:chips-filled" {...props}></Icon>
