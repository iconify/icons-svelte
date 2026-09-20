<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxck67bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxck67bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bulb-filled" {...props}></Icon>
