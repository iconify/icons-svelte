<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qra_k5bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qra_k5bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:frame-filled" {...props}></Icon>
