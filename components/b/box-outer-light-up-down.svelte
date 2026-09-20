<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st2be1bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="st2be1bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-down" {...props}></Icon>
