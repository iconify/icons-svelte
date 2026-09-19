<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu4jmcblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu4jmcblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:briefcase-alt-filled" {...props}></Icon>
