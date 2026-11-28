<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a23eap52e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a23eap52e primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-to-line-duotone" {...props}></Icon>
