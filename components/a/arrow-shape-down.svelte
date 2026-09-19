<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1xn9bcet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f1xn9bcet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-down" {...props}></Icon>
