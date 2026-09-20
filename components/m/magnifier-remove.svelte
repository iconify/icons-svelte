<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soj-5vb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="soj-5vb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:magnifier-remove" {...props}></Icon>
