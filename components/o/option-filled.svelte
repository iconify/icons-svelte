<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2_t99qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us2_t99qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:option-filled" {...props}></Icon>
