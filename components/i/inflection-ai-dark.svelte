<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6xx_uqow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a6xx_uqow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inflection-ai-dark" {...props}></Icon>
