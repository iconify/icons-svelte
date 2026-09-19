<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fti5rt4zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fti5rt4zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:facebook" {...props}></Icon>
