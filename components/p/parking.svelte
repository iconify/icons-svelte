<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7xhgpk0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z7xhgpk0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:parking" {...props}></Icon>
