<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py3qm5roi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py3qm5roi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microgenetics" {...props}></Icon>
