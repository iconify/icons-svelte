<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-g3icchj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-g3icchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-bottom-right-filled" {...props}></Icon>
