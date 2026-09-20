<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj85dljpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj85dljpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:npm" {...props}></Icon>
