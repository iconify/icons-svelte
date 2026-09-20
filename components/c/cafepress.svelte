<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cukae7boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cukae7boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cafepress" {...props}></Icon>
