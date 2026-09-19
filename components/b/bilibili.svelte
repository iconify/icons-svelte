<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we_-wp3rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="we_-wp3rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bilibili" {...props}></Icon>
