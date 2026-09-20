<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5v1l59cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5v1l59cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-upward-duotone" {...props}></Icon>
