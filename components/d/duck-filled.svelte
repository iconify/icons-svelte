<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm5sbg_7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm5sbg_7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:duck-filled" {...props}></Icon>
