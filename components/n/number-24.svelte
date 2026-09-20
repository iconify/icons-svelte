<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5m9iq4dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5m9iq4dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:number-24" {...props}></Icon>
