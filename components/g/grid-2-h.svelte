<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl27z12fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl27z12fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:grid-2-h" {...props}></Icon>
