<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-5pybak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="g8-5pybak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:lock-open" {...props}></Icon>
