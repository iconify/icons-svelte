<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9dvb922t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9dvb922t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-lock-open-outline" {...props}></Icon>
