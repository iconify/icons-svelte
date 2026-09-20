<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gglh1cybb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gglh1cybb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-left" {...props}></Icon>
