<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o79dnnrab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o79dnnrab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-windows" {...props}></Icon>
