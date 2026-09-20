<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuptj_q1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kuptj_q1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpmyadmin" {...props}></Icon>
