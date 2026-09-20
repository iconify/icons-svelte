<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipfz-qbde.css';
import '../../css/l/l0z5z-bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ipfz-qbde"/><path clip-rule="evenodd" class="l0z5z-bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:password-solid" {...props}></Icon>
