<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he-waqbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he-waqbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:coin-filled" {...props}></Icon>
