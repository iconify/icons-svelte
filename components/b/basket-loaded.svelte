<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z67tz0b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z67tz0b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:basket-loaded" {...props}></Icon>
