<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn1_y7b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn1_y7b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-radius-filled" {...props}></Icon>
