<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxa-w1bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxa-w1bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-office-line" {...props}></Icon>
