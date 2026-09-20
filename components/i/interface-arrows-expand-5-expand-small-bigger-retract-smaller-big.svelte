<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0kqobc-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="t0kqobc-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-expand-5-expand-small-bigger-retract-smaller-big" {...props}></Icon>
