<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc-ejurpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc-ejurpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:layers-minus" {...props}></Icon>
