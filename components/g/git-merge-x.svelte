<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e75amibgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e75amibgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:git-merge-x" {...props}></Icon>
