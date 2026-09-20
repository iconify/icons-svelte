<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evnwlobir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":441,"height":441};
const content = `<path class="evnwlobir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deno-dark" {...props}></Icon>
