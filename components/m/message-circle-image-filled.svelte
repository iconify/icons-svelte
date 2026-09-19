<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upt-3cclz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upt-3cclz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-image-filled" {...props}></Icon>
