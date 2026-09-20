<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn4jr074g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn4jr074g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alibaba" {...props}></Icon>
