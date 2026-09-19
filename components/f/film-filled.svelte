<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozb0_ubof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozb0_ubof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:film-filled" {...props}></Icon>
