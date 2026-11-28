<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zktde8bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zktde8bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:door" {...props}></Icon>
