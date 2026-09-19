<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-fmy342m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":449,"height":512};
const content = `<path class="q-fmy342m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fossil" {...props}></Icon>
