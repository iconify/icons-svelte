<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdyfjf78j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdyfjf78j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-call" {...props}></Icon>
