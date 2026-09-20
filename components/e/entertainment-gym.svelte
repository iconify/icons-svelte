<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw5rifb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qw5rifb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:entertainment-gym" {...props}></Icon>
