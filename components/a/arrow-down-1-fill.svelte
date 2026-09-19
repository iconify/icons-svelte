<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab6tnjbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab6tnjbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-1-fill" {...props}></Icon>
