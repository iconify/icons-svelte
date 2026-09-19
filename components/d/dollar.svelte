<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moux05b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":24};
const content = `<path class="moux05b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dollar" {...props}></Icon>
