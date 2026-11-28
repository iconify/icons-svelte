<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8y9gvioh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8y9gvioh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bed-solid" {...props}></Icon>
