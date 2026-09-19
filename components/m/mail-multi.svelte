<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7gw2sb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7gw2sb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:mail-multi" {...props}></Icon>
