<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyzqvq11k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyzqvq11k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-circle-down" {...props}></Icon>
