<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1mpvmb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1mpvmb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-heart-outline" {...props}></Icon>
