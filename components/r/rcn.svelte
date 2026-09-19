<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fot1ehb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fot1ehb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:rcn" {...props}></Icon>
