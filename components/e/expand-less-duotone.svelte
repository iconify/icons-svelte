<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8q0sd-0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8q0sd-0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-less-duotone" {...props}></Icon>
