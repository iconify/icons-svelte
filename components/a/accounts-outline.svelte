<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci9979btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ci9979btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:accounts-outline" {...props}></Icon>
