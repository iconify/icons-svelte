<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8y2fgjvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j8y2fgjvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:paperplane-fill" {...props}></Icon>
