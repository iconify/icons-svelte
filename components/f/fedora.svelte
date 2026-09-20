<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7gzqcy7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7gzqcy7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fedora" {...props}></Icon>
