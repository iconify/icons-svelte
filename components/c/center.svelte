<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs30_xv-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xs30_xv-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:center" {...props}></Icon>
