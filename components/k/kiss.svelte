<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beayis30x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="beayis30x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:kiss" {...props}></Icon>
