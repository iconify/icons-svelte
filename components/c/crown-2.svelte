<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_1wvtowb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_1wvtowb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:crown-2" {...props}></Icon>
