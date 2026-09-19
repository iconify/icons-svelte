<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms0e8vi6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ms0e8vi6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:high-heeled-shoe" {...props}></Icon>
