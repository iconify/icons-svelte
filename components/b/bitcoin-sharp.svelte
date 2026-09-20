<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xku04_bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xku04_bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bitcoin-sharp" {...props}></Icon>
