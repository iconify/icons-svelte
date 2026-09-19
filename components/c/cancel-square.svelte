<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9d_8tvzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9d_8tvzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cancel-square" {...props}></Icon>
