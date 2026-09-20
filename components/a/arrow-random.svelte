<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu376izwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu376izwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-random" {...props}></Icon>
