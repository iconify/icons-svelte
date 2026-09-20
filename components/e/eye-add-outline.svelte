<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc1cj_fzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc1cj_fzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-add-outline" {...props}></Icon>
