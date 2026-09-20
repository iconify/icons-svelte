<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du5n3hbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="du5n3hbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:bug" {...props}></Icon>
