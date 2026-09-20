<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d09fbgrfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d09fbgrfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lens-shade-bold" {...props}></Icon>
