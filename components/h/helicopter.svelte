<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj6jd7bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uj6jd7bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:helicopter" {...props}></Icon>
