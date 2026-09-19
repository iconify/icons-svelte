<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5xvgdb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5xvgdb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-front-door-locked" {...props}></Icon>
