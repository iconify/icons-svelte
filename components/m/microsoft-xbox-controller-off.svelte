<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns_c3jf9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns_c3jf9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-xbox-controller-off" {...props}></Icon>
