<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj6cv4bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bj6cv4bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:finder" {...props}></Icon>
