<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh5ie8beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh5ie8beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pail-off" {...props}></Icon>
