<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k49hg70lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k49hg70lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bicycle-wash" {...props}></Icon>
