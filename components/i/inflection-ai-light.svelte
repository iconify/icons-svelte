<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oywncb5to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oywncb5to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inflection-ai-light" {...props}></Icon>
