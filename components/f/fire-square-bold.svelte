<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amyujzb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amyujzb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-square-bold" {...props}></Icon>
