<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-6-cac6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-6-cac6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:regex" {...props}></Icon>
