<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/g96sazbxl.css';
import '../../css/q/qoebb6b-x.css';
import '../../css/f/fxsft62au.css';
import '../../css/m/maw6_-12u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<defs><mask id="SVGIVSQUd5t"><g class="v3_i3wktz"><path class="g96sazbxl"/><path class="qoebb6b-x"/><path class="fxsft62au"/></g></mask></defs><path mask="url(#SVGIVSQUd5t)" class="maw6_-12u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:disk-one" {...props}></Icon>
