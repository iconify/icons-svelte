<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecydh6bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ecydh6bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-right" {...props}></Icon>
