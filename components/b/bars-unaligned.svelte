<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1iahpb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m1iahpb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-unaligned" {...props}></Icon>
