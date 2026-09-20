<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip_2e3jip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip_2e3jip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eurs" {...props}></Icon>
