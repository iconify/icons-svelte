<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s59fp7b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s59fp7b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:edit-page" {...props}></Icon>
