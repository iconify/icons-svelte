<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2fllcyck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="h2fllcyck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bandage-fill" {...props}></Icon>
