<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkm56n7je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jkm56n7je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-centered" {...props}></Icon>
