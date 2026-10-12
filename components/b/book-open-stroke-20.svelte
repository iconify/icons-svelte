<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0p78bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ln0p78bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-open-stroke-20" {...props}></Icon>
