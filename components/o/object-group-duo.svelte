<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z982bgb5u.css';
import '../../css/c/cieejvb9y.css';
import '../../css/g/gei8aufil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z982bgb5u"/><path class="cieejvb9y"/><path class="gei8aufil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:object-group-duo" {...props}></Icon>
