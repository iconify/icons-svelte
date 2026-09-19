<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpaej3bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tpaej3bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:frown-open" {...props}></Icon>
