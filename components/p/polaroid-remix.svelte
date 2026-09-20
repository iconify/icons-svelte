<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k18_m_dye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k18_m_dye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:polaroid-remix" {...props}></Icon>
