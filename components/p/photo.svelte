<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc72tzb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dc72tzb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:photo" {...props}></Icon>
