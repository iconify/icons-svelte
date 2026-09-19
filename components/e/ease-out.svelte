<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrwky9boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrwky9boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ease-out" {...props}></Icon>
