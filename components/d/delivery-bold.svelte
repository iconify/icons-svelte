<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy6o8dbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6o8dbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:delivery-bold" {...props}></Icon>
