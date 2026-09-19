<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gae0srbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gae0srbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:pushpin" {...props}></Icon>
