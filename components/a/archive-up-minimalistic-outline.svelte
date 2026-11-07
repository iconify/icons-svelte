<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywujp7bzh.css';
import '../../css/p/p9comhf0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywujp7bzh"/><path clip-rule="evenodd" class="p9comhf0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-up-minimalistic-outline" {...props}></Icon>
