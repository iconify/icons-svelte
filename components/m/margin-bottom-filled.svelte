<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj3p1-bpn.css';
import '../../css/e/exda4zbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj3p1-bpn"/><rect class="exda4zbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:margin-bottom-filled" {...props}></Icon>
