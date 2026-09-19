<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbj2ozb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbj2ozb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-upload-fill" {...props}></Icon>
