<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sut_hcb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sut_hcb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-left-duo" {...props}></Icon>
