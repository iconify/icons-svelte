<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obxojtb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="obxojtb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:circle-filled" {...props}></Icon>
