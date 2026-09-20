<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7e9-ibfi.css';
import '../../css/k/ksyanacfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7e9-ibfi"/><path clip-rule="evenodd" class="ksyanacfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:phone-duotone" {...props}></Icon>
