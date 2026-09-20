<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8h8i1yra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8h8i1yra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hotel-fill" {...props}></Icon>
