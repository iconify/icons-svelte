<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztl5zacac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="ztl5zacac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:rocket" {...props}></Icon>
