<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgb78bb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgb78bb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-1-filled" {...props}></Icon>
