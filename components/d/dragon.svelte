<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s43o5kpge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="s43o5kpge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dragon" {...props}></Icon>
