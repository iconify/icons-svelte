<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyik3ye0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyik3ye0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-corner-rounded" {...props}></Icon>
