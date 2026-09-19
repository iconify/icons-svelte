<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ete8q8b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ete8q8b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:mask" {...props}></Icon>
