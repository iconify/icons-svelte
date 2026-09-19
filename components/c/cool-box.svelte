<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhk9d3brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qhk9d3brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cool-box" {...props}></Icon>
