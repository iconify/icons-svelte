<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3q429ycn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3q429ycn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:headphonezone" {...props}></Icon>
