<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2uofa4ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c2uofa4ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bolt" {...props}></Icon>
