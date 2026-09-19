<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv035x6ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kv035x6ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:grinning-face-with-star-eyes" {...props}></Icon>
