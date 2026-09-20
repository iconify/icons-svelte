<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncxk4z-et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncxk4z-et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lina" {...props}></Icon>
