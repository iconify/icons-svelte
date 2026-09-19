<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eboq2oy7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eboq2oy7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-left-circle-filled" {...props}></Icon>
