<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su1r-hbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="su1r-hbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-check-bold" {...props}></Icon>
