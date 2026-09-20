<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-5h5pbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-5h5pbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-arrow-up" {...props}></Icon>
