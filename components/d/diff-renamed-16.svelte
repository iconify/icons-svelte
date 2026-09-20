<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkc-cckkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tkc-cckkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-renamed-16" {...props}></Icon>
