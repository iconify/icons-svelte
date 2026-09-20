<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weck2_bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weck2_bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openfaas" {...props}></Icon>
