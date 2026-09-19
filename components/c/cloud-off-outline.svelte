<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk6u7080f.css';
import '../../css/n/nrl8gacpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yk6u7080f"/><path class="nrl8gacpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cloud-off-outline" {...props}></Icon>
