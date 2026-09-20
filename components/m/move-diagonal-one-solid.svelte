<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwu2i75do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwu2i75do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-diagonal-one-solid" {...props}></Icon>
