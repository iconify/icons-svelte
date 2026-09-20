<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha2wewu4o.css';
import '../../css/e/e15g94bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha2wewu4o"/><path clip-rule="evenodd" class="e15g94bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-bing-bold" {...props}></Icon>
