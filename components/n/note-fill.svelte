<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5v5fg1lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5v5fg1lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:note-fill" {...props}></Icon>
