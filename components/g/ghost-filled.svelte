<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piui6-jib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piui6-jib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ghost-filled" {...props}></Icon>
