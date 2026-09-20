<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak6ukobkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6ukobkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-left" {...props}></Icon>
