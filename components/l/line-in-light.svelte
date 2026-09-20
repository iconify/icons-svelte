<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt3vlejol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt3vlejol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-in-light" {...props}></Icon>
