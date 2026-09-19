<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoy6yv3cj.css';
import '../../css/y/yef4huqia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xoy6yv3cj"/><path class="yef4huqia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackfolder" {...props}></Icon>
