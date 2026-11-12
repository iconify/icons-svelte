<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9-d-dbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9-d-dbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dagster-light" {...props}></Icon>
