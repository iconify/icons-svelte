<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttq0anb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttq0anb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-4-square-fill" {...props}></Icon>
