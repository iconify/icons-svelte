<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_q_wbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ia_q_wbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:expand-alt" {...props}></Icon>
