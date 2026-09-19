<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polygon points="1.75 1.75 14.25 1.75 14.25 3.25 9.25 8.75 9.25 12.75 6.75 14.25 6.75 8.75 1.75 3.25" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:filter" {...props}></Icon>
