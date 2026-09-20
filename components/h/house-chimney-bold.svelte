<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zni5_hulp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zni5_hulp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:house-chimney-bold" {...props}></Icon>
