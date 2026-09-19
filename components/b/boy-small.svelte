<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gld0fn8un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gld0fn8un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:boy-small" {...props}></Icon>
