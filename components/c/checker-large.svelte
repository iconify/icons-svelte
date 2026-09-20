<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi2z2u4mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xi2z2u4mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checker-large" {...props}></Icon>
