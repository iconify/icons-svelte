<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h22y-lv-g.css';
import '../../css/f/fwk_nlbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2195.9,"height":2430.9};
const content = `<path class="h22y-lv-g"/><path class="fwk_nlbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-analytics" {...props}></Icon>
