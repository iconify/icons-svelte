<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swa6fxbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swa6fxbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:rdio-logo-solid" {...props}></Icon>
