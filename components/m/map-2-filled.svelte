<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_oty8pjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_oty8pjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-2-filled" {...props}></Icon>
