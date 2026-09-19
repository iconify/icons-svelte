<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrdpt1k-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":488};
const content = `<path class="qrdpt1k-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:lovedsgn" {...props}></Icon>
