<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aprx8ebqb.css';
import '../../css/i/i3h3u4txt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aprx8ebqb"/><path class="i3h3u4txt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-helm-open" {...props}></Icon>
