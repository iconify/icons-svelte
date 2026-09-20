<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0rj54bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0rj54bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:polestar" {...props}></Icon>
