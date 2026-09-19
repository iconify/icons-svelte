<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebr0d7qtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebr0d7qtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:reasonstudios-alt" {...props}></Icon>
