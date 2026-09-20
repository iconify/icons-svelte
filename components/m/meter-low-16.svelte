<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrbv2j1ga.css';
import '../../css/q/qtl0jcblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xrbv2j1ga"/><path class="qtl0jcblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:meter-low-16" {...props}></Icon>
