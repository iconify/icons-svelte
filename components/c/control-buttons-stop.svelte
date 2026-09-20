<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bia8e8idd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bia8e8idd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-stop" {...props}></Icon>
