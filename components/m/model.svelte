<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thw6rvjmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="thw6rvjmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:model" {...props}></Icon>
