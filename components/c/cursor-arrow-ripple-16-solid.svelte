<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euzd-wbuo.css';
import '../../css/z/z3wkr3_hc.css';
import '../../css/o/o4lxspb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="euzd-wbuo"/><path class="z3wkr3_hc"/><path class="o4lxspb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-ripple-16-solid" {...props}></Icon>
