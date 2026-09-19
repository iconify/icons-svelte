<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0m9b6bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t0m9b6bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cat" {...props}></Icon>
