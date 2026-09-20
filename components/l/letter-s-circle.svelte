<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc9_4z-8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc9_4z-8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-s-circle" {...props}></Icon>
