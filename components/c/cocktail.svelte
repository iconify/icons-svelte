<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkk3sjblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="nkk3sjblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cocktail" {...props}></Icon>
