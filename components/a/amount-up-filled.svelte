<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo4yz7b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lo4yz7b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-up-filled" {...props}></Icon>
