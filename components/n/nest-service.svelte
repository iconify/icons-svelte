<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkbd6vbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lkbd6vbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nest-service" {...props}></Icon>
