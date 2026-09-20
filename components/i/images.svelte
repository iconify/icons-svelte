<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyg4zbcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyg4zbcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:images" {...props}></Icon>
