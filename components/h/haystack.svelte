<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pht4l3yoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pht4l3yoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:haystack" {...props}></Icon>
