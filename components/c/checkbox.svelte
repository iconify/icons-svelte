<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niekoc4bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niekoc4bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:checkbox" {...props}></Icon>
