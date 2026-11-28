<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aev2ndtkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aev2ndtkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-upload-x" {...props}></Icon>
