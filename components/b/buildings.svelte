<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znfwbkb8v.css';
import '../../css/p/pqx863b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znfwbkb8v"/><path class="pqx863b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:buildings" {...props}></Icon>
