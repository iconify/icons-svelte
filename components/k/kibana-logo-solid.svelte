<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tffli5bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tffli5bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kibana-logo-solid" {...props}></Icon>
