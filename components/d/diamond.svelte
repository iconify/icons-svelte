<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-qo8nbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o-qo8nbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:diamond" {...props}></Icon>
