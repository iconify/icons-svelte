<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot-2adjyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-2adjyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mapillary" {...props}></Icon>
