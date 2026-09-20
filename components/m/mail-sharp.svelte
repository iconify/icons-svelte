<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsujqd_kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsujqd_kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-sharp" {...props}></Icon>
