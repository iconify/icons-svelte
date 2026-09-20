<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7y3x5kge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f7y3x5kge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-diff-16" {...props}></Icon>
