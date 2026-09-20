<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3natyb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3natyb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:magnet" {...props}></Icon>
