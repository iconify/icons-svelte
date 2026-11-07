<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s28m-k17m.css';
import '../../css/p/p9comhf0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s28m-k17m"/><path clip-rule="evenodd" class="p9comhf0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-minimalistic-outline" {...props}></Icon>
