<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9io2_wvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9io2_wvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gallery-vertical" {...props}></Icon>
