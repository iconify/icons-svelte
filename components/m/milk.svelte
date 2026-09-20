<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsjoa2b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fsjoa2b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:milk" {...props}></Icon>
