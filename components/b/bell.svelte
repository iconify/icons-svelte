<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-px0gyax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="l-px0gyax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bell" {...props}></Icon>
