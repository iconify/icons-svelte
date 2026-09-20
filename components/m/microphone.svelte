<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5w-93bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v5w-93bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:microphone" {...props}></Icon>
