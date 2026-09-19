<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o55fdr30x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o55fdr30x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-chevron-right" {...props}></Icon>
