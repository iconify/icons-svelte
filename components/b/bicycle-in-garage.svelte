<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-15vo-zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c-15vo-zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-in-garage" {...props}></Icon>
