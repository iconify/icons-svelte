<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7li-lboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7li-lboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-line" {...props}></Icon>
