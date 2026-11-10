<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du9gf8b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="du9gf8b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:hair" {...props}></Icon>
