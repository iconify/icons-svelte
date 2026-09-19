<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0oa6dbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a0oa6dbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-pull-request-create" {...props}></Icon>
