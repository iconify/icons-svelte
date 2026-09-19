<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btnvbfz_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="btnvbfz_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:livejournal" {...props}></Icon>
