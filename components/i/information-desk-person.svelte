<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrz8nvb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nrz8nvb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:information-desk-person" {...props}></Icon>
