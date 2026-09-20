<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmoodnbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmoodnbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachekafka" {...props}></Icon>
