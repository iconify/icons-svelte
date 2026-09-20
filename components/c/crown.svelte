<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-kj1jbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-kj1jbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:crown" {...props}></Icon>
