<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po1kqwbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po1kqwbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-scuba" {...props}></Icon>
