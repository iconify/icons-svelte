<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrsc13pcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrsc13pcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bitcoin" {...props}></Icon>
