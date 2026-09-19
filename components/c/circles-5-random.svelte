<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy23x9ztz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uy23x9ztz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circles-5-random" {...props}></Icon>
