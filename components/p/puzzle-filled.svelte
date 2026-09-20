<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbedh9_zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jbedh9_zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:puzzle-filled" {...props}></Icon>
