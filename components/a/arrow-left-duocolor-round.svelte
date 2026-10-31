<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_4b-y3-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_4b-y3-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-duocolor-round" {...props}></Icon>
