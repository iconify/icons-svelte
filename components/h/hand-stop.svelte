<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7p7t6wxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x7p7t6wxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:hand-stop" {...props}></Icon>
