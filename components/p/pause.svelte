<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t04w3ucra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t04w3ucra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pause" {...props}></Icon>
