<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3bvj6h0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3bvj6h0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-connect-filled" {...props}></Icon>
