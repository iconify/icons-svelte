<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gipn88bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gipn88bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-left" {...props}></Icon>
