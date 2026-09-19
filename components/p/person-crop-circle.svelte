<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4w4s00tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i4w4s00tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle" {...props}></Icon>
