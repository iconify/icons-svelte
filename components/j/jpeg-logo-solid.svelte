<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo6wm__mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo6wm__mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:jpeg-logo-solid" {...props}></Icon>
