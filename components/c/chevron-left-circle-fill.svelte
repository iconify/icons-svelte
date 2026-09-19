<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku7oqxm4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ku7oqxm4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-left-circle-fill" {...props}></Icon>
