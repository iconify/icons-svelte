<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/medowg-8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="medowg-8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:heading-1" {...props}></Icon>
