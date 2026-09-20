<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziiv523bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziiv523bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:khronos-group" {...props}></Icon>
