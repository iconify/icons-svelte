<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_0ryua6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_0ryua6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-up-right-fill-round" {...props}></Icon>
