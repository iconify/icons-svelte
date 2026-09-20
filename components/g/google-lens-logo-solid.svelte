<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq_pwhb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq_pwhb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-lens-logo-solid" {...props}></Icon>
