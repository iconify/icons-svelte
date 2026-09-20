<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttalljb2j.css';
import '../../css/p/p_n9afb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttalljb2j"/><path class="p_n9afb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:crack-filled" {...props}></Icon>
