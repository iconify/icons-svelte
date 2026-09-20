<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfc18wb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pfc18wb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:align-vertical-distribute" {...props}></Icon>
