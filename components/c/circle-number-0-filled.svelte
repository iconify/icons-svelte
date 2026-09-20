<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgr-qlbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgr-qlbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-number-0-filled" {...props}></Icon>
