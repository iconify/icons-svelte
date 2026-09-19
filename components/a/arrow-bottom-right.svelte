<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk65jhv8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk65jhv8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-bottom-right" {...props}></Icon>
