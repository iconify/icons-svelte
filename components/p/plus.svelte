<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gto6vda9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gto6vda9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:plus" {...props}></Icon>
