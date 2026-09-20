<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj5emybiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nj5emybiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:clipboard" {...props}></Icon>
