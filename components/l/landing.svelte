<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1yytzwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="py1yytzwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:landing" {...props}></Icon>
