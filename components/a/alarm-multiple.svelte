<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/metz4187g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="metz4187g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:alarm-multiple" {...props}></Icon>
