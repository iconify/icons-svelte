<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csesmy2vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="csesmy2vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:invert-small" {...props}></Icon>
