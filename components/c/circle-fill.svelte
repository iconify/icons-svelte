<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdv_x32nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdv_x32nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-fill" {...props}></Icon>
