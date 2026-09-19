<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbo646wjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jbo646wjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-down-arrow-up" {...props}></Icon>
