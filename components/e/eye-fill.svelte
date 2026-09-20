<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/holrsn7wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="holrsn7wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:eye-fill" {...props}></Icon>
