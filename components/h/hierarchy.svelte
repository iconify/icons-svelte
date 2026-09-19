<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymk_ijrgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ymk_ijrgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:hierarchy" {...props}></Icon>
