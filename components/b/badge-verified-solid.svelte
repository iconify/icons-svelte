<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scx1z0ypn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scx1z0ypn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:badge-verified-solid" {...props}></Icon>
