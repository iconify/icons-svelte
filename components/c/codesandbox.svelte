<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnr5p9b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":600,"height":600};
const content = `<path clip-rule="evenodd" class="qnr5p9b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codesandbox" {...props}></Icon>
