<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtwaxhb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtwaxhb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:jewish-star" {...props}></Icon>
