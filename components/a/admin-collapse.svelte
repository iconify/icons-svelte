<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbs-mwb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zbs-mwb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-collapse" {...props}></Icon>
