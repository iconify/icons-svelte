<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6a4gs6js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6a4gs6js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-off" {...props}></Icon>
