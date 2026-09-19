<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y82uu8bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y82uu8bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-0-filled" {...props}></Icon>
