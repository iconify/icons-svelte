<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5-1m4u-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b5-1m4u-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-alt-circle-fill" {...props}></Icon>
