<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffr2t8xmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ffr2t8xmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heavy-dollar-sign-small" {...props}></Icon>
