<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djr3dcz0j.css';
import '../../css/z/zf5h5-ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djr3dcz0j"/><path class="zf5h5-ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:creators-club-duotone" {...props}></Icon>
