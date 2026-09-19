<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szmw6ngwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szmw6ngwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:deskphone-filled" {...props}></Icon>
