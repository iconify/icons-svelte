<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_j4uacvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_j4uacvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bitstamp" {...props}></Icon>
