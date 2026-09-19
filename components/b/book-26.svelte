<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj73_vt_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kj73_vt_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-26" {...props}></Icon>
