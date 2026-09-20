<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj3chubbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj3chubbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:earthquake-fill" {...props}></Icon>
