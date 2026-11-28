<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk97fbb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk97fbb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-off-solid" {...props}></Icon>
