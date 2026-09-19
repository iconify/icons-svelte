<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_4euzb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m_4euzb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clock-small-filled" {...props}></Icon>
