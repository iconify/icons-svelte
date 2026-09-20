<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeo5pg9kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oeo5pg9kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:margin-bottom" {...props}></Icon>
