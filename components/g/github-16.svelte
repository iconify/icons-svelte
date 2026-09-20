<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q94xyqb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q94xyqb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:github-16" {...props}></Icon>
