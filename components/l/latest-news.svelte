<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb39_n0xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb39_n0xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:latest-news" {...props}></Icon>
