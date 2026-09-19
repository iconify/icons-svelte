<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_k02bocx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_k02bocx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-0-circle-fill" {...props}></Icon>
