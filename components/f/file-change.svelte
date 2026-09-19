<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdh_y_bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bdh_y_bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:file-change" {...props}></Icon>
