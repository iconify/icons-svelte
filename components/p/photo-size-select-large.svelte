<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acv8zdb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="acv8zdb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:photo-size-select-large" {...props}></Icon>
