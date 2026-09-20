<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_34kqjcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f_34kqjcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:address-book-outline" {...props}></Icon>
