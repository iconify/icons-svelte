<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fagdp1b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fagdp1b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-0306m-outline-24px" {...props}></Icon>
