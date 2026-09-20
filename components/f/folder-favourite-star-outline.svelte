<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckp9iqb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckp9iqb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favourite-star-outline" {...props}></Icon>
