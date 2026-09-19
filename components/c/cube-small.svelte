<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz1gjqb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vz1gjqb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cube-small" {...props}></Icon>
