<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftckqgulz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftckqgulz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bandcamp" {...props}></Icon>
