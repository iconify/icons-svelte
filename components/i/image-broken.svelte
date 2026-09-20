<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uva2xdm3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uva2xdm3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-broken" {...props}></Icon>
