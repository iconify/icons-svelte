<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj6g5_6ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj6g5_6ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:key-solid" {...props}></Icon>
