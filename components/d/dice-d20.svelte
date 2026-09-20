<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcf9lrb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fcf9lrb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-d20" {...props}></Icon>
