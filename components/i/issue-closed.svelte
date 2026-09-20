<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0zltcte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ak0zltcte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-closed" {...props}></Icon>
