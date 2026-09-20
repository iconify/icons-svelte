<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stzzxb4zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stzzxb4zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reply-all" {...props}></Icon>
