<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vacy5raqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vacy5raqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:hard-drive" {...props}></Icon>
