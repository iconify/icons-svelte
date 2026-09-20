<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qui3_ycrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qui3_ycrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ladder" {...props}></Icon>
