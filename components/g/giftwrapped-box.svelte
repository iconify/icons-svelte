<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brx9nkbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="brx9nkbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:giftwrapped-box" {...props}></Icon>
