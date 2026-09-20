<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv_90lbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv_90lbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-r-small" {...props}></Icon>
