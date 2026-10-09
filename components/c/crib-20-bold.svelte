<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzdvkjb-z.css';
import '../../css/k/ke2lxtdne.css';
import '../../css/m/m_laitx2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wzdvkjb-z"/><path class="ke2lxtdne"/><path class="m_laitx2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crib-20-bold" {...props}></Icon>
