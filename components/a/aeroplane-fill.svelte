<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fljd5rbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fljd5rbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:aeroplane-fill" {...props}></Icon>
