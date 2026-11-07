<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nihi5z84r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nihi5z84r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-heart-outline" {...props}></Icon>
