<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0_0xjbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o0_0xjbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-sparks" {...props}></Icon>
