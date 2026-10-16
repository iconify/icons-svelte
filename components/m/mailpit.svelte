<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olgn96bqv.css';
import '../../css/j/jse14viep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":132.292,"height":121.708};
const content = `<path class="olgn96bqv"/><path class="jse14viep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mailpit" {...props}></Icon>
