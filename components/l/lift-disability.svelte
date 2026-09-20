<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsicu5rxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dsicu5rxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lift-disability" {...props}></Icon>
