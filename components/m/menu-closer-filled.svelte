<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2vh03bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2vh03bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menu-closer-filled" {...props}></Icon>
