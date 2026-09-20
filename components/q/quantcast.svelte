<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2aqz483q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2aqz483q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:quantcast" {...props}></Icon>
