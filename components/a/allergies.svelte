<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h87imzhaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="h87imzhaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:allergies" {...props}></Icon>
