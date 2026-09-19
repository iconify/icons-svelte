<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et1wd_cfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="et1wd_cfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizeupleft" {...props}></Icon>
