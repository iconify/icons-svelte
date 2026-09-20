<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p50ynifab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p50ynifab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-plus" {...props}></Icon>
