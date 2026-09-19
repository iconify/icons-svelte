<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3m0v5bbq.css';
import '../../css/l/l4ea3-bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3m0v5bbq duoicon-secondary-layer"/><path class="duoicon-primary-layer l4ea3-bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:camera" {...props}></Icon>
