<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj7t04z_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gj7t04z_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:amazon" {...props}></Icon>
