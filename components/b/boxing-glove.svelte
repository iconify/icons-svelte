<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvk_gpczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvk_gpczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:boxing-glove" {...props}></Icon>
