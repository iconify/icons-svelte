<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isi942u_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="isi942u_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:android" {...props}></Icon>
