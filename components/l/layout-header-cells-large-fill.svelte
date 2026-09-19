<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i39dyzhvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i39dyzhvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-header-cells-large-fill" {...props}></Icon>
