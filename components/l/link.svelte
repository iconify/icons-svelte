<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2o82qbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n2o82qbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:link" {...props}></Icon>
