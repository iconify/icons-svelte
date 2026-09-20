<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eobs_dz0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eobs_dz0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cloud-off" {...props}></Icon>
