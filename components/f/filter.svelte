<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbeb90ock.css';
import '../../css/h/hmezibw8e.css';
import '../../css/m/mnjrvv75q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbeb90ock wm-k"/><path class="hmezibw8e wm-k"/><path class="mnjrvv75q wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:filter" {...props}></Icon>
