<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg9xyjbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lg9xyjbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:lemon" {...props}></Icon>
