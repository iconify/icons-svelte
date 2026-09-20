<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm31op6ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qm31op6ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-logo-solid" {...props}></Icon>
