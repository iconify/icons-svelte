<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz7cuwb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vz7cuwb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-header-cells" {...props}></Icon>
