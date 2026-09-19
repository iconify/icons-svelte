<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0273qbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0273qbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:direction-left-down" {...props}></Icon>
