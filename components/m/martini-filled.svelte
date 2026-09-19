<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdxa_275p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdxa_275p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:martini-filled" {...props}></Icon>
