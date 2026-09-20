<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq-sgi9nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mq-sgi9nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:leaf-filled" {...props}></Icon>
