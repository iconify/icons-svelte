<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me-v67brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="me-v67brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-add-1-expand-cross-buttons-button-more-remove-plus-add" {...props}></Icon>
