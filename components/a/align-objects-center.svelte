<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4_4oj5ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4_4oj5ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:align-objects-center" {...props}></Icon>
