<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_38s2b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_38s2b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:align-justify" {...props}></Icon>
