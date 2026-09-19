<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e92jr9qgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e92jr9qgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cat-face-small" {...props}></Icon>
