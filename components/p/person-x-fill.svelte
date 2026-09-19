<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yosik5bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yosik5bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-x-fill" {...props}></Icon>
