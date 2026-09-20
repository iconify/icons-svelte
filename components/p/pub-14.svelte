<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df7l_ob9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="df7l_ob9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:pub-14" {...props}></Icon>
