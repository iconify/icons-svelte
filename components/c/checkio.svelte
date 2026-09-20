<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo79yf13r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo79yf13r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:checkio" {...props}></Icon>
