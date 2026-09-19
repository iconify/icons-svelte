<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_jrdpbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r_jrdpbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:databases" {...props}></Icon>
