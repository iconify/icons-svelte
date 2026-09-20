<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f777k-bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f777k-bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-minus-outline" {...props}></Icon>
