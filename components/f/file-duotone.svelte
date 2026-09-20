<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw2v_fbbh.css';
import '../../css/g/gu10zdn1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw2v_fbbh"/><path class="gu10zdn1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:file-duotone" {...props}></Icon>
