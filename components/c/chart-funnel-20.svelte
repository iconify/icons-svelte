<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyz37m_ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nyz37m_ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-funnel-20" {...props}></Icon>
