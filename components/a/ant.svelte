<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/najw6-2ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="najw6-2ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:ant" {...props}></Icon>
