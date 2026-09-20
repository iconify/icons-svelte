<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qamb87bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qamb87bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cattle-grid" {...props}></Icon>
