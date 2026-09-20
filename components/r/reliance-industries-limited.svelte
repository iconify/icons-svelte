<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01mb6a3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w01mb6a3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:reliance-industries-limited" {...props}></Icon>
