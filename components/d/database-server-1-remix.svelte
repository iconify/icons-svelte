<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_s86eyys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m_s86eyys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-server-1-remix" {...props}></Icon>
