<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvp0-qsza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jvp0-qsza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-branch" {...props}></Icon>
