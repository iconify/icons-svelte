<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwxccybgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jwxccybgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrows-rotate-right-slash" {...props}></Icon>
