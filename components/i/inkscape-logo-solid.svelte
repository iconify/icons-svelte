<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzfw9dz6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzfw9dz6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:inkscape-logo-solid" {...props}></Icon>
