<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do95htb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="do95htb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:not-sent" {...props}></Icon>
