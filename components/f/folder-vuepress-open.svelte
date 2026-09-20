<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlcn2cboi.css';
import '../../css/x/x01ecnbfj.css';
import '../../css/m/mltmzybmp.css';
import '../../css/c/c51w9-bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vlcn2cboi"/><path class="x01ecnbfj"/><path class="mltmzybmp"/><path class="c51w9-bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-vuepress-open" {...props}></Icon>
