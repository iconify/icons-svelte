<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-z20k46c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-z20k46c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-logo-2" {...props}></Icon>
