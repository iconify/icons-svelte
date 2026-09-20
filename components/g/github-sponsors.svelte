<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5ecocnoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t5ecocnoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:github-sponsors" {...props}></Icon>
