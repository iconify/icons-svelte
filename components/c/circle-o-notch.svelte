<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suoc8zbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1728};
const content = `<path class="suoc8zbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:circle-o-notch" {...props}></Icon>
