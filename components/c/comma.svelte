<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdan5fs-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":154,"height":767};
const content = `<path class="xdan5fs-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:comma" {...props}></Icon>
