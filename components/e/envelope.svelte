<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9iirbbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="k9iirbbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:envelope" {...props}></Icon>
