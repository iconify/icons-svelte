<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx9z9xbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx9z9xbhj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:library-duotone" {...props}></Icon>
