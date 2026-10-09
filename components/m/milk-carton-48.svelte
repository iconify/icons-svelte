<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytre_iyqf.css';
import '../../css/a/aqm8hp2ux.css';
import '../../css/a/a6d6nheff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ytre_iyqf"/><path class="aqm8hp2ux"/><path class="a6d6nheff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:milk-carton-48" {...props}></Icon>
