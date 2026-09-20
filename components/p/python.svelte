<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrbwxfd2d.css';
import '../../css/h/h697m9a0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrbwxfd2d"/><path class="h697m9a0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:python" {...props}></Icon>
