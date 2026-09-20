<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guhgj0rvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guhgj0rvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fil" {...props}></Icon>
