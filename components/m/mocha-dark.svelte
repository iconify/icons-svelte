<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hynasbbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1084};
const content = `<path class="hynasbbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mocha-dark" {...props}></Icon>
