<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_mj__btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_mj__btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-stadia-logo-block" {...props}></Icon>
