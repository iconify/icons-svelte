<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg7n2eb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":182,"height":981};
const content = `<path class="lg7n2eb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:parenright" {...props}></Icon>
