<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay3_mubnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay3_mubnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-minimize" {...props}></Icon>
