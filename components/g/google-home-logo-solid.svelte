<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhh9m-5ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhh9m-5ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-home-logo-solid" {...props}></Icon>
