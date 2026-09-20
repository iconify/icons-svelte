<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auzj7tbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="auzj7tbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:n64-outline" {...props}></Icon>
