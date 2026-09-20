<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sco8suych.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="sco8suych"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:info" {...props}></Icon>
