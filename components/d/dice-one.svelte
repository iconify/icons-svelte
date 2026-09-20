<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1c3vggea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c1c3vggea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-one" {...props}></Icon>
