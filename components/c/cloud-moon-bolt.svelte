<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpf4gjb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zpf4gjb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-moon-bolt" {...props}></Icon>
