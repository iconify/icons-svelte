<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcwdn0bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jcwdn0bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plug-fill-20" {...props}></Icon>
