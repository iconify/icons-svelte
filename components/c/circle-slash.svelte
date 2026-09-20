<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3-tzbc-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="b3-tzbc-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:circle-slash" {...props}></Icon>
