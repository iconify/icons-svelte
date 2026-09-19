<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoe9-6brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uoe9-6brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dot" {...props}></Icon>
