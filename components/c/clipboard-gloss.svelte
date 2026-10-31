<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1ok0bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp1ok0bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-gloss" {...props}></Icon>
