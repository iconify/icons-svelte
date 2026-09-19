<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yetb_qhpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yetb_qhpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:columns" {...props}></Icon>
