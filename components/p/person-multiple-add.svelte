<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dact7tbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dact7tbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-multiple-add" {...props}></Icon>
