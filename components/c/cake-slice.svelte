<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzci_0zyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzci_0zyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cake-slice" {...props}></Icon>
