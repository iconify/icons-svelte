<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae3981pxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ae3981pxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:protect" {...props}></Icon>
