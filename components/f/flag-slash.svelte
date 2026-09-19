<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3f_t1esf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c3f_t1esf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:flag-slash" {...props}></Icon>
