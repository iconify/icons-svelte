<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7o5oob0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h7o5oob0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:phone" {...props}></Icon>
