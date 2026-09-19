<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjw8wvbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjw8wvbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:objects-vertical-center" {...props}></Icon>
