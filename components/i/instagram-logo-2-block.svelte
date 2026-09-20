<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctw_mi0zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctw_mi0zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instagram-logo-2-block" {...props}></Icon>
