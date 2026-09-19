<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq064gb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bq064gb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pause" {...props}></Icon>
