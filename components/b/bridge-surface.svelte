<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gji4buisi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gji4buisi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bridge-surface" {...props}></Icon>
