<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl9i0ubuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl9i0ubuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-slice-7" {...props}></Icon>
