<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qua-qqbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qua-qqbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:chevrons-left" {...props}></Icon>
