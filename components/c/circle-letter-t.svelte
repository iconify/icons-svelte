<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij1jslgcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ij1jslgcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-t" {...props}></Icon>
