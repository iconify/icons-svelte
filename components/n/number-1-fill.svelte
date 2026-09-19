<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0z_3kboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0z_3kboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-1-fill" {...props}></Icon>
