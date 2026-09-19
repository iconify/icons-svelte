<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_e9v2bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b_e9v2bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:eye-slash" {...props}></Icon>
