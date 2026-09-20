<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzssd7d7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzssd7d7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lg" {...props}></Icon>
