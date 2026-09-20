<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3u28ea3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3u28ea3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:byte" {...props}></Icon>
