<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4xr-1bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h4xr-1bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:keyboard-solid" {...props}></Icon>
