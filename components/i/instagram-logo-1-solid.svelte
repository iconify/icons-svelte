<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt3uecrng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pt3uecrng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:instagram-logo-1-solid" {...props}></Icon>
