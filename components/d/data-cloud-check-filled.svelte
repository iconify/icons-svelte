<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj91_xmgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj91_xmgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:data-cloud-check-filled" {...props}></Icon>
