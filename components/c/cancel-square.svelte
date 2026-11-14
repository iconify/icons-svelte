<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk46vdvtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk46vdvtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cancel-square" {...props}></Icon>
