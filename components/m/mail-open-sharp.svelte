<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msppc204j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msppc204j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-open-sharp" {...props}></Icon>
