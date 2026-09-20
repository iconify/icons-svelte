<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw8u_cvdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw8u_cvdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-funds-fill" {...props}></Icon>
