<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcha-w7qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcha-w7qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-bold" {...props}></Icon>
