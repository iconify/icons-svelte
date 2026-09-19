<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etxt3sbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etxt3sbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar-close" {...props}></Icon>
