<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsdbv17zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1400.1,"height":452.4,"left":-0.03,"top":-0.03};
const content = `<path class="wsdbv17zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:harvard" {...props}></Icon>
