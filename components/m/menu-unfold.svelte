<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suyzr6jpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="suyzr6jpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:menu-unfold" {...props}></Icon>
