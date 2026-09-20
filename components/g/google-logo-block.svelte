<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh_0sfwki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh_0sfwki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-logo-block" {...props}></Icon>
