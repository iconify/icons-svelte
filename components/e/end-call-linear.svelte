<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9m55n4ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9m55n4ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-linear" {...props}></Icon>
