<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfhtqhbtz.css';
import '../../css/d/du0tax8oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pfhtqhbtz"/><path class="du0tax8oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jar-20-bold" {...props}></Icon>
