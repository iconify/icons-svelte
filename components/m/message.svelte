<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polygon points="1.75 14.25 1.75 2.75 14.25 2.75 14.25 11.25 5.75 11.25" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:message" {...props}></Icon>
