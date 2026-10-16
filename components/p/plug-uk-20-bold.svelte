<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs3jkhbrx.css';
import '../../css/p/paodlxbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bs3jkhbrx"/><path class="paodlxbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-uk-20-bold" {...props}></Icon>
