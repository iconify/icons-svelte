<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4p6ypbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i4p6ypbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pencil-16-solid" {...props}></Icon>
