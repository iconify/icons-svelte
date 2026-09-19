<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzpxyeb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vzpxyeb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:person-with-folded-hands" {...props}></Icon>
