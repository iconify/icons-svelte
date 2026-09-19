<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bus8sus2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bus8sus2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:coffee" {...props}></Icon>
