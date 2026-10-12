<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klbmyhl8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="klbmyhl8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-increase-20" {...props}></Icon>
