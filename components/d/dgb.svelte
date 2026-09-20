<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih_rsbb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih_rsbb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dgb" {...props}></Icon>
