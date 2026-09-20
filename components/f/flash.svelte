<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miodk4bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="miodk4bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flash" {...props}></Icon>
