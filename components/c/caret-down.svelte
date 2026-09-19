<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9z93jo_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k9z93jo_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:caret-down" {...props}></Icon>
