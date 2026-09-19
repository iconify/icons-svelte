<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6fj2acav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6fj2acav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:health" {...props}></Icon>
