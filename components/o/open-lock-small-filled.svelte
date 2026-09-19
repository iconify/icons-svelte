<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gums8tbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gums8tbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:open-lock-small-filled" {...props}></Icon>
