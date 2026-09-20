<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx7iuhb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hx7iuhb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-down-circle" {...props}></Icon>
