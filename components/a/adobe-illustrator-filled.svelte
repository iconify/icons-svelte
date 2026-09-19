<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od80o1xlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="od80o1xlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-illustrator-filled" {...props}></Icon>
