<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_nt2_bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nt2_bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:multiply-circle-multiple-outline" {...props}></Icon>
