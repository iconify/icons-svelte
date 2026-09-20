<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfs981ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qqfs981ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-ear-nose-throat" {...props}></Icon>
