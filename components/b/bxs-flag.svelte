<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq1_qoxvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq1_qoxvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-flag" {...props}></Icon>
