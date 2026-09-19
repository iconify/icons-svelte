<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuhtm-b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yuhtm-b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-9-square-fill" {...props}></Icon>
