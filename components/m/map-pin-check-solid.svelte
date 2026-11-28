<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwvkl-j3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwvkl-j3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:map-pin-check-solid" {...props}></Icon>
