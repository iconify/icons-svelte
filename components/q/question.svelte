<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqj4sr0ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pqj4sr0ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:question" {...props}></Icon>
