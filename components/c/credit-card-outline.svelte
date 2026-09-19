<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqv6kbcvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqv6kbcvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:credit-card-outline" {...props}></Icon>
