<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szxt5sb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szxt5sb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bus3-filled" {...props}></Icon>
