<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_-66ebji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h_-66ebji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:laravel-outline" {...props}></Icon>
