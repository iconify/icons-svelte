<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5jb4sbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5jb4sbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-t-circle-outline" {...props}></Icon>
