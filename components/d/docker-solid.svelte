<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1je8vb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="y1je8vb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:docker-solid" {...props}></Icon>
