<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v56pg-bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="v56pg-bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:question" {...props}></Icon>
