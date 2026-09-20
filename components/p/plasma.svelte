<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wji3m3b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wji3m3b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:plasma" {...props}></Icon>
