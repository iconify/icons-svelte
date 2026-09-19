<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb75rybht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb75rybht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:book-open" {...props}></Icon>
