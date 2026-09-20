<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7cu_u-yk.css';
import '../../css/p/p351x--2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x7cu_u-yk"/><circle class="p351x--2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:blender" {...props}></Icon>
