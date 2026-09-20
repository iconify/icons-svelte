<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiel0ej8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kiel0ej8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-forward" {...props}></Icon>
