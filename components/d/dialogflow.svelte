<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wii_33l7g.css';
import '../../css/z/z05w6h9vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wii_33l7g"/><path class="z05w6h9vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dialogflow" {...props}></Icon>
