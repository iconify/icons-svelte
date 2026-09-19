<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm1mhyw_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rm1mhyw_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:power" {...props}></Icon>
