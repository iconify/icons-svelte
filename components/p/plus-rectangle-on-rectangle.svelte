<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv912ko5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fv912ko5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:plus-rectangle-on-rectangle" {...props}></Icon>
