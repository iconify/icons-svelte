<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1ge8bg6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h1ge8bg6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-circle-fill" {...props}></Icon>
