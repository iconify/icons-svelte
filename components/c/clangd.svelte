<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c48zpqb1g.css';
import '../../css/a/ae2dujtsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c48zpqb1g"/><path class="ae2dujtsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:clangd" {...props}></Icon>
