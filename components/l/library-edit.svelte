<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw7wcab6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw7wcab6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:library-edit" {...props}></Icon>
