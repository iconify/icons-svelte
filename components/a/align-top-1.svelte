<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz6lxvbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yz6lxvbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:align-top-1" {...props}></Icon>
