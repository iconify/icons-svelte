<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb24tq28w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eb24tq28w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:arrow-alt-circle-left" {...props}></Icon>
