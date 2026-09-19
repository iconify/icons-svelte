<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm0tryqzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dm0tryqzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-ten-small-filled" {...props}></Icon>
