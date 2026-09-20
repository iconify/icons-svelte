<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5zv_pbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5zv_pbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:gender-lesbian-2-solid" {...props}></Icon>
