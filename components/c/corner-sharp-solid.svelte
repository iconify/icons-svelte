<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcozhwbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcozhwbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-sharp-solid" {...props}></Icon>
