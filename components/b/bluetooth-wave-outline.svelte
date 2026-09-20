<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb6shej8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sb6shej8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-wave-outline" {...props}></Icon>
