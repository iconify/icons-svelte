<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ted_08wrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ted_08wrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-in" {...props}></Icon>
