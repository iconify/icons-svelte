<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2b3d_yuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l2b3d_yuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:page-number-solid" {...props}></Icon>
