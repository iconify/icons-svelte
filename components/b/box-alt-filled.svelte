<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_8drnl1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_8drnl1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:box-alt-filled" {...props}></Icon>
