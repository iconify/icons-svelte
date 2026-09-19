<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_93su88i.css';
import '../../css/v/viznwcc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_93su88i"/><path class="viznwcc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-image-add" {...props}></Icon>
