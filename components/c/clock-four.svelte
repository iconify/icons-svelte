<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajs0hsgkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ajs0hsgkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:clock-four" {...props}></Icon>
