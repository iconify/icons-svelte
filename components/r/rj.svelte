<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-m-2byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v7-m-2byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rj" {...props}></Icon>
