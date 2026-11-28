<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eux9rf7bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eux9rf7bu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-duotone" {...props}></Icon>
