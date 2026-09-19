<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sookxta7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sookxta7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:dongchedi" {...props}></Icon>
