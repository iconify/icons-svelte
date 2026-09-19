<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j48wigbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j48wigbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-api-gateway" {...props}></Icon>
