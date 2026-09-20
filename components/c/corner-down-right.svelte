<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oupyt1nha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oupyt1nha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:corner-down-right" {...props}></Icon>
