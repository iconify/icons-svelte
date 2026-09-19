<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li8w93b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="li8w93b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:error-computer" {...props}></Icon>
