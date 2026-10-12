<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pydxmub-s.css';
import '../../css/s/sru-zac9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pydxmub-s"/><path class="sru-zac9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:history-fill-20" {...props}></Icon>
