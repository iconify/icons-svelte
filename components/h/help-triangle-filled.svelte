<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px1frhb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px1frhb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:help-triangle-filled" {...props}></Icon>
