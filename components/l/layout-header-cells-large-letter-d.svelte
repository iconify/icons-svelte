<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv33-qbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uv33-qbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-header-cells-large-letter-d" {...props}></Icon>
