<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chl7dpbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chl7dpbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:folder-open" {...props}></Icon>
