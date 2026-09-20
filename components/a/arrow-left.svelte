<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smecvub7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="smecvub7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-left" {...props}></Icon>
