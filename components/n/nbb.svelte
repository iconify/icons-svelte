<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgbh3otig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgbh3otig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nbb" {...props}></Icon>
