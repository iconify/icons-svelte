<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaeket_ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iaeket_ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-filled" {...props}></Icon>
