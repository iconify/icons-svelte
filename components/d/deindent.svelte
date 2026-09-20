<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb8cwrcqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pb8cwrcqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:deindent" {...props}></Icon>
