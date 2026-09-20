<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa0l2acmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aa0l2acmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:linkedin" {...props}></Icon>
