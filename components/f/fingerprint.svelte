<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki_1ns98y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki_1ns98y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fingerprint" {...props}></Icon>
