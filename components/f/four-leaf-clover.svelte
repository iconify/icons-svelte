<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq1nambya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rq1nambya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:four-leaf-clover" {...props}></Icon>
