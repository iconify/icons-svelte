<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0p60rdek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0p60rdek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gatsby-fill" {...props}></Icon>
