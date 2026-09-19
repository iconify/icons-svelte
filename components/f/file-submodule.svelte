<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpp7pcb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gpp7pcb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:file-submodule" {...props}></Icon>
