<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4c8pd5le.css';
import '../../css/c/clgeaqb1x.css';
import '../../css/y/yq8uffbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4c8pd5le"/><path class="clgeaqb1x"/><path class="yq8uffbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-web-component-outline" {...props}></Icon>
