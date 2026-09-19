<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1lcx54am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1lcx54am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-rounded-detail" {...props}></Icon>
