<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9kx4f5-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9kx4f5-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-fill" {...props}></Icon>
