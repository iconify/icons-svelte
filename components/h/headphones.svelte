<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpz5y8b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wpz5y8b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:headphones" {...props}></Icon>
