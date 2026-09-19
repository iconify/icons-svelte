<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myv0d9bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myv0d9bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:rewind-circle" {...props}></Icon>
