<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciqk79q9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciqk79q9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dog-heart" {...props}></Icon>
