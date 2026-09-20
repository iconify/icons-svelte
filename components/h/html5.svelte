<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbs6rebdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pbs6rebdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:html5" {...props}></Icon>
