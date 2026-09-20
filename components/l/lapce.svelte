<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlilyp2hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlilyp2hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lapce" {...props}></Icon>
