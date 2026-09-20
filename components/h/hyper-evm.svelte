<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oal_t8bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oal_t8bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hyper-evm" {...props}></Icon>
