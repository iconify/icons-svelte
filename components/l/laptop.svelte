<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx2181yer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx2181yer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:laptop" {...props}></Icon>
