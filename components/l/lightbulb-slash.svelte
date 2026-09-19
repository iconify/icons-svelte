<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucl5_zvmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ucl5_zvmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lightbulb-slash" {...props}></Icon>
