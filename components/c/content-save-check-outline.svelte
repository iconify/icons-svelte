<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlgyd4b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgyd4b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-check-outline" {...props}></Icon>
