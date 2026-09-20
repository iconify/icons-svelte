<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9he1imzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9he1imzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:drag-drop-2" {...props}></Icon>
