<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rew-o_dyy.css';
import '../../css/u/ubz5-631s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rew-o_dyy"/><path class="ubz5-631s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:coldfusion" {...props}></Icon>
