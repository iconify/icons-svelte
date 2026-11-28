<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2we6kbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2we6kbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-search" {...props}></Icon>
