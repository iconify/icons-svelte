<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs_yneb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qs_yneb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-16" {...props}></Icon>
