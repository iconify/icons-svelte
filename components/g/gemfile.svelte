<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt_08xbdc.css';
import '../../css/e/e1l_1_bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pt_08xbdc"/><path class="e1l_1_bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gemfile" {...props}></Icon>
