<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btm1bkawd.css';
import '../../css/x/x-53_-bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="btm1bkawd"/><path class="x-53_-bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:group" {...props}></Icon>
