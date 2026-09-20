<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki8i-ccap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ki8i-ccap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gamesave" {...props}></Icon>
