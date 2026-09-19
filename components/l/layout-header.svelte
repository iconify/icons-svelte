<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu5zfpqgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hu5zfpqgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-header" {...props}></Icon>
