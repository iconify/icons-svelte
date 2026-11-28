<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ok0ac6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-ok0ac6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bell-solid" {...props}></Icon>
