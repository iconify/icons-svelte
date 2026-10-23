<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wask6o2nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wask6o2nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:a-large-small" {...props}></Icon>
