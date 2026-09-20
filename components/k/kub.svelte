<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky3n2u_io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky3n2u_io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kub" {...props}></Icon>
