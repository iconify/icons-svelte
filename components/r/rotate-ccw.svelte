<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwt63lncr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwt63lncr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rotate-ccw" {...props}></Icon>
