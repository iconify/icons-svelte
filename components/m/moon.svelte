<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jayb4bcqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jayb4bcqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:moon" {...props}></Icon>
