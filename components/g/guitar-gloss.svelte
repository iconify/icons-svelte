<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee8ekuboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee8ekuboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:guitar-gloss" {...props}></Icon>
