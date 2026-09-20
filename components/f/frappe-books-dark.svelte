<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_v2c-7io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_v2c-7io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-books-dark" {...props}></Icon>
