<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5dsrdbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c5dsrdbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:feedback" {...props}></Icon>
