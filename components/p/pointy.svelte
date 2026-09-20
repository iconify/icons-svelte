<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1si36-1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1si36-1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pointy" {...props}></Icon>
