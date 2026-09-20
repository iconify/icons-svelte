<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwuf2jxfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":400};
const content = `<path class="mwuf2jxfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ibm" {...props}></Icon>
