<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nebj-zb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nebj-zb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-bold" {...props}></Icon>
