<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4bk4-bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i4bk4-bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:adjustments" {...props}></Icon>
