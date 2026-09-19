<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbpjll5ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pbpjll5ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:avatar" {...props}></Icon>
