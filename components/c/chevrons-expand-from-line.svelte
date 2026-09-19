<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muiyoab3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="muiyoab3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevrons-expand-from-line" {...props}></Icon>
