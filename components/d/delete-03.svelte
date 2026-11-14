<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbdl0_bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbdl0_bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-03" {...props}></Icon>
