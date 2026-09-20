<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyq6eeli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tyyq6eeli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:desklamp-outline" {...props}></Icon>
