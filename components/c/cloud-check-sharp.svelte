<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km_0wyb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km_0wyb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-check-sharp" {...props}></Icon>
