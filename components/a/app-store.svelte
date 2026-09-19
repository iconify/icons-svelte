<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuadcwjxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuadcwjxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:app-store" {...props}></Icon>
