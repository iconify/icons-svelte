<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugd4lfbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ugd4lfbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-stash-apply" {...props}></Icon>
