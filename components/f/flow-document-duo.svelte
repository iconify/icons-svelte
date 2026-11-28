<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4qsytige.css';
import '../../css/i/i3jzowbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4qsytige secondary"/><path class="i3jzowbmb primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-document-duo" {...props}></Icon>
