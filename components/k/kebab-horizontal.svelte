<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oukk7ab7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="oukk7ab7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:kebab-horizontal" {...props}></Icon>
