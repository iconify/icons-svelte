<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0q2btitu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k0q2btitu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gabbr-logo-solid" {...props}></Icon>
