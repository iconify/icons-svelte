<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/espppac0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="espppac0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-broken" {...props}></Icon>
