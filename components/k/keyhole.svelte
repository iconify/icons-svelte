<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egm_2b38y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="egm_2b38y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:keyhole" {...props}></Icon>
