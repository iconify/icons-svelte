<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln33uabds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ln33uabds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layers-vertical" {...props}></Icon>
