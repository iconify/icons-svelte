<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3b_m5t_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3b_m5t_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-photo-logo-solid" {...props}></Icon>
