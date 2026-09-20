<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8yx3mb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q8yx3mb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:beer" {...props}></Icon>
