<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzddf_b4l.css';
import '../../css/l/lvp7n1b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzddf_b4l"/><path class="lvp7n1b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:exclamation-triangle" {...props}></Icon>
