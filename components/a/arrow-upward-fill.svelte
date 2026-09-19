<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fof7p7mfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fof7p7mfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-upward-fill" {...props}></Icon>
