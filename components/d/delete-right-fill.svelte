<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7bxybbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i7bxybbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:delete-right-fill" {...props}></Icon>
