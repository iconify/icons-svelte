<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polygon points="4.75 2.75 11.25 2.75 14.25 6.25 8 13.25 1.75 6.25" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:gem" {...props}></Icon>
