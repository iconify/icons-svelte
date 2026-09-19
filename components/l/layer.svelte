<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6j_ppv8x.css';
import '../../css/h/h0ktb0wiz.css';
import '../../css/h/hj6ofxbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6j_ppv8x"/><path class="h0ktb0wiz"/><path class="hj6ofxbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:layer" {...props}></Icon>
