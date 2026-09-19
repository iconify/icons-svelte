<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5r96s-qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5r96s-qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:meh-filled" {...props}></Icon>
