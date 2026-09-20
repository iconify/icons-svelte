<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_on6713p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m_on6713p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:location-target-2-remix" {...props}></Icon>
