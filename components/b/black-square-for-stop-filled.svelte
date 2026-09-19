<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/web3leb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="web3leb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-square-for-stop-filled" {...props}></Icon>
