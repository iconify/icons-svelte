<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afqkvoqte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afqkvoqte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:flame-kindling" {...props}></Icon>
