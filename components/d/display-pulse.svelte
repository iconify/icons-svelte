<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u32249byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u32249byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:display-pulse" {...props}></Icon>
