<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exu4375zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exu4375zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:headphone-alt" {...props}></Icon>
