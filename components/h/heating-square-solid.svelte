<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e22xqcbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e22xqcbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:heating-square-solid" {...props}></Icon>
