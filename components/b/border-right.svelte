<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m58mo2jnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m58mo2jnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:border-right" {...props}></Icon>
