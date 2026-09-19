<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eragz99eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eragz99eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:commenting" {...props}></Icon>
