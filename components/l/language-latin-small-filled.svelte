<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k93f81brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k93f81brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-latin-small-filled" {...props}></Icon>
