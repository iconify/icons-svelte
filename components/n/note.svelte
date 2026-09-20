<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7jtysb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="c7jtysb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:note" {...props}></Icon>
