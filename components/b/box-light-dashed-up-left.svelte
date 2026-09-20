<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3eothw3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y3eothw3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-up-left" {...props}></Icon>
