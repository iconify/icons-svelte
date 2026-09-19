<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn61jjbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sn61jjbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-bottom" {...props}></Icon>
