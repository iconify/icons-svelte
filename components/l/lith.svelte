<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svbrmobav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svbrmobav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lith" {...props}></Icon>
