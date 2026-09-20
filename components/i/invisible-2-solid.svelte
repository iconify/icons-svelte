<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9uj-ij0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v9uj-ij0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:invisible-2-solid" {...props}></Icon>
