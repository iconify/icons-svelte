<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to2z3sr5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="to2z3sr5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-left-right" {...props}></Icon>
