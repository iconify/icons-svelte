<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6c77uj-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="x6c77uj-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pepper-hot" {...props}></Icon>
