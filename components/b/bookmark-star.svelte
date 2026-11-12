<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee9p8obgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee9p8obgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-star" {...props}></Icon>
