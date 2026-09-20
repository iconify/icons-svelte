<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqbx_ob3b.css';
import '../../css/u/uxebd5iiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbx_ob3b"/><path class="uxebd5iiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:book" {...props}></Icon>
