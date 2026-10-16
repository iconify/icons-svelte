<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_05epb2z.css';
import '../../css/y/y3_5i7bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m_05epb2z"/><path class="y3_5i7bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pc-tower-20-bold" {...props}></Icon>
