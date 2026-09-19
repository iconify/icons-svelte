<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnf61wnjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rnf61wnjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:display-dot-matrix-small" {...props}></Icon>
