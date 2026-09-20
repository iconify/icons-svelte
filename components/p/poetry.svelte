<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1b6_0b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1b6_0b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:poetry" {...props}></Icon>
