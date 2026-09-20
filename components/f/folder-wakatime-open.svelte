<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxf38ybrm.css';
import '../../css/q/qrlb8jbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yxf38ybrm"/><path class="qrlb8jbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-wakatime-open" {...props}></Icon>
