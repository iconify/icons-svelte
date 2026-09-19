<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaqeoccxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jaqeoccxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-4-square-fill" {...props}></Icon>
