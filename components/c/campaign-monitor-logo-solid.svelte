<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xye4-h2xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xye4-h2xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:campaign-monitor-logo-solid" {...props}></Icon>
