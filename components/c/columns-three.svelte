<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1cy7yb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cy7yb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:columns-three" {...props}></Icon>
