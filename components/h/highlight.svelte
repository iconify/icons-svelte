<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlqboo-0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dlqboo-0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:highlight" {...props}></Icon>
