<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc6-f2oia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tc6-f2oia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:github-inverted" {...props}></Icon>
