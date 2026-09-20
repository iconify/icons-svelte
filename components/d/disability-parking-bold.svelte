<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj1pmedun.css';
import '../../css/n/nuy3iacup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj1pmedun"/><path class="nuy3iacup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:disability-parking-bold" {...props}></Icon>
