<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kagc6bc1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kagc6bc1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mouse-pointer" {...props}></Icon>
