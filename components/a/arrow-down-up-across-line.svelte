<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq-3olb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dq-3olb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-down-up-across-line" {...props}></Icon>
