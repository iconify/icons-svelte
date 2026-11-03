<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnfy8db-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nnfy8db-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:git-branch-16-solid" {...props}></Icon>
