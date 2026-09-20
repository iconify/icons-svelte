<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpmt7cn-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vpmt7cn-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bookmark" {...props}></Icon>
