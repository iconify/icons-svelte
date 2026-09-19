<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm4ww6bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jm4ww6bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-exclamation" {...props}></Icon>
