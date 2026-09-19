<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz-mjg0wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sz-mjg0wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:grid" {...props}></Icon>
