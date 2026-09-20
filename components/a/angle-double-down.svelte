<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc86bf0gu.css';
import '../../css/h/htispzbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hc86bf0gu"/><path class="htispzbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:angle-double-down" {...props}></Icon>
