<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polygon points="5.25 1.75 10.75 1.75 14.25 5.25 14.25 10.75 10.75 14.25 5.25 14.25 1.75 10.75 1.75 5.25" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:octagon" {...props}></Icon>
