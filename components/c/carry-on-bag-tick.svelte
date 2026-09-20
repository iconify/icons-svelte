<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf4gv2feu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf4gv2feu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:carry-on-bag-tick" {...props}></Icon>
