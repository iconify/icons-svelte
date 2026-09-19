<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axbgkns7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":898,"height":1024};
const content = `<path class="axbgkns7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:forest" {...props}></Icon>
