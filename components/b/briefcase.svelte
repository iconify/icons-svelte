<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh6t7r4um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fh6t7r4um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:briefcase" {...props}></Icon>
