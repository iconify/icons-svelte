<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-sh_5dhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-sh_5dhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bubble2" {...props}></Icon>
