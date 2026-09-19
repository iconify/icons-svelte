<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx-n44b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dx-n44b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-cells" {...props}></Icon>
