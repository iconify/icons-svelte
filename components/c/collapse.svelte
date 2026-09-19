<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abtjy3v0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abtjy3v0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:collapse" {...props}></Icon>
