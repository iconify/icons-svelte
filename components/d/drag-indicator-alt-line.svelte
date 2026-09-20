<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py41x_zcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py41x_zcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:drag-indicator-alt-line" {...props}></Icon>
