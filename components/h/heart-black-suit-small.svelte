<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgya-abtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hgya-abtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-black-suit-small" {...props}></Icon>
