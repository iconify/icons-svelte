<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppv6zu5ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppv6zu5ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-7-circle" {...props}></Icon>
