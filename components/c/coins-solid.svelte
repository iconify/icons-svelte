<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulh-6-blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulh-6-blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:coins-solid" {...props}></Icon>
