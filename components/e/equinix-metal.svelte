<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh2yl7b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh2yl7b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:equinix-metal" {...props}></Icon>
