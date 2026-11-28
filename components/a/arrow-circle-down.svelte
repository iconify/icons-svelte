<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq057jbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq057jbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-circle-down" {...props}></Icon>
